<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pybr84bnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pybr84bnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:command-gloss" {...props}></Icon>
