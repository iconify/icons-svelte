<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x50z2w0vt.css';
import '../../css/u/ujlm800om.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<defs><path id="SVGNnUjDexH" class="x50z2w0vt"/></defs><use href="#SVGNnUjDexH"/><path class="ujlm800om"/><use href="#SVGNnUjDexH"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:phone-landscape" {...props}></Icon>
