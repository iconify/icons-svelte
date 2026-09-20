<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilax4nweo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ilax4nweo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:mic" {...props}></Icon>
