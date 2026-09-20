<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4y3k-p3k.css';
import '../../css/n/nv3l533ys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a4y3k-p3k"/><path class="nv3l533ys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:opendns" {...props}></Icon>
