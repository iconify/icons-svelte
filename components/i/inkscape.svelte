<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unl4ioy1a.css';
import '../../css/u/u27h525fw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="unl4ioy1a"/><path class="u27h525fw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:inkscape" {...props}></Icon>
