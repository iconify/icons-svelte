<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kg1bwt3th.css';
import '../../css/c/cdocj7brz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kg1bwt3th"/><path class="cdocj7brz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-stencil" {...props}></Icon>
