<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgq2ujbcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dgq2ujbcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:rocket" {...props}></Icon>
