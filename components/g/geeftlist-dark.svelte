<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6xfb8lhn.css';
import '../../css/e/ebf-dhbmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u6xfb8lhn"/><path class="ebf-dhbmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:geeftlist-dark" {...props}></Icon>
