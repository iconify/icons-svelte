<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9e7o7bng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x9e7o7bng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:heading-4" {...props}></Icon>
