<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/arr8fdc7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="arr8fdc7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:cpu" {...props}></Icon>
