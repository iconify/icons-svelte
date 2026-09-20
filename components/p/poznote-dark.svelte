<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dw65ihi1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dw65ihi1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:poznote-dark" {...props}></Icon>
