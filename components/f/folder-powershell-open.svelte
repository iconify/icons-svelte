<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/da1i54d5m.css';
import '../../css/b/bsbw6h5dv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="da1i54d5m"/><path class="bsbw6h5dv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-powershell-open" {...props}></Icon>
