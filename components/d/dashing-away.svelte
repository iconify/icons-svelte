<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2w3uac9z.css';
import '../../css/e/edv2k_o8i.css';
import '../../css/e/eqoo6tulb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="d2w3uac9z"/><path class="edv2k_o8i"/><path class="eqoo6tulb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:dashing-away" {...props}></Icon>
