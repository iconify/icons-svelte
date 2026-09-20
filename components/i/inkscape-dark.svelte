<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ssfz_ebsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ssfz_ebsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:inkscape-dark" {...props}></Icon>
