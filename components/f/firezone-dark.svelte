<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bh45pgscz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bh45pgscz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:firezone-dark" {...props}></Icon>
