<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co37yjsqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="co37yjsqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:fortran" {...props}></Icon>
