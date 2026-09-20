<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/koj4gublb.css';
import '../../css/o/ofw11lk8d.css';
import '../../css/y/y6rebfbtb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="koj4gublb"/><path class="ofw11lk8d"/><path class="y6rebfbtb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:password-pusher" {...props}></Icon>
