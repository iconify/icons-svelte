<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7l54zb3f.css';
import '../../css/i/ijxvr0blg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="c7l54zb3f"/><path class="ijxvr0blg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-constant" {...props}></Icon>
