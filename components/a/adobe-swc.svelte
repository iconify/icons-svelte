<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfsq92b5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pfsq92b5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:adobe-swc" {...props}></Icon>
