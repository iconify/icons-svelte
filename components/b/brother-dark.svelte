<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i112icc0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i112icc0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:brother-dark" {...props}></Icon>
