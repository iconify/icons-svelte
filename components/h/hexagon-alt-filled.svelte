<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9baqwbzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a9baqwbzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:hexagon-alt-filled" {...props}></Icon>
