<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u0dz0lbab.css';
import '../../css/c/c8p6lwb2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u0dz0lbab"/><path class="c8p6lwb2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rauthy-light" {...props}></Icon>
