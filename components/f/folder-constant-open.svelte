<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u48mzcbuj.css';
import '../../css/i/ijxvr0blg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="u48mzcbuj"/><path class="ijxvr0blg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-constant-open" {...props}></Icon>
