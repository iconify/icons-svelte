<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7ml1bbhq.css';
import '../../css/k/k08isbc9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t7ml1bbhq"/><path class="k08isbc9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cobalt" {...props}></Icon>
