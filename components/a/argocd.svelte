<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1b9jcbak.css';
import '../../css/n/nywwhyjhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="u1b9jcbak"/><path class="nywwhyjhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:argocd" {...props}></Icon>
