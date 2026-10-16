<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oegrs6bql.css';
import '../../css/s/sdign8ysz.css';
import '../../css/k/kl3wgccdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="oegrs6bql"/><path class="sdign8ysz"/><path class="kl3wgccdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:receipt-refund-48" {...props}></Icon>
