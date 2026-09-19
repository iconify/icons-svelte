<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3t7sz9mf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j3t7sz9mf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:badge-filled" {...props}></Icon>
