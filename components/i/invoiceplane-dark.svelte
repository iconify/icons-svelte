<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5yu1qb-n.css';
import '../../css/t/tmnoc9bjp.css';
import '../../css/z/zeq616bts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k5yu1qb-n"/><path class="tmnoc9bjp"/><path class="zeq616bts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:invoiceplane-dark" {...props}></Icon>
