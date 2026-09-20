<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-fmsbcaz.css';
import '../../css/t/tpfmbf6bd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="p-fmsbcaz"/><path class="tpfmbf6bd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-environment-open" {...props}></Icon>
