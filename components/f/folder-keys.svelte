<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l47nr7bbh.css';
import '../../css/i/iywcnqb5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l47nr7bbh"/><path class="iywcnqb5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-keys" {...props}></Icon>
