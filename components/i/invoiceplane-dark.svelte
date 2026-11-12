<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yt9ppcjum.css';
import '../../css/a/au4zb9b5u.css';
import '../../css/z/zeq616bts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yt9ppcjum"/><path class="au4zb9b5u"/><path class="zeq616bts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:invoiceplane-dark" {...props}></Icon>
