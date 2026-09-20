<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c84_js1xt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c84_js1xt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:national-grid" {...props}></Icon>
