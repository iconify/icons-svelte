<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drmq9wbtb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="drmq9wbtb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:mongoose" {...props}></Icon>
