<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mar1fqi3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mar1fqi3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:area-search" {...props}></Icon>
