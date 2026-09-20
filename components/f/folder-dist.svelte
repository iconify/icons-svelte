<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tb5pi-bnv.css';
import '../../css/c/c3tt83vyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tb5pi-bnv"/><path class="c3tt83vyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-dist" {...props}></Icon>
