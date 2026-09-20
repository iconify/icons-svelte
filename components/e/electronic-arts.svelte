<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4tdwlciq.css';
import '../../css/c/ca1v0e7az.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<ellipse class="m4tdwlciq"/><path class="ca1v0e7az"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:electronic-arts" {...props}></Icon>
