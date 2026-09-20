<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bumpl1bqw.css';
import '../../css/h/hosfmobjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bumpl1bqw"/><path class="hosfmobjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:receipt-wrangler" {...props}></Icon>
