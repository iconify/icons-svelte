<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ug4ifvviu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ug4ifvviu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:connectivity-filled" {...props}></Icon>
