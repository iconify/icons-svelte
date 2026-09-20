<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tf6uy_bxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tf6uy_bxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:markdown" {...props}></Icon>
