<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ogoa_1oaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ogoa_1oaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:paperless-home-dark" {...props}></Icon>
