<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kaqgtyjjh.css';
import '../../css/c/cr2fezr1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kaqgtyjjh"/><path class="cr2fezr1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:autocaliweb" {...props}></Icon>
