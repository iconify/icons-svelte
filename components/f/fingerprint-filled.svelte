<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-a9cubfv.css';
import '../../css/b/bh3jo8buu.css';
import '../../css/b/bqx68zbbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e-a9cubfv"/><path class="bh3jo8buu"/><path class="bqx68zbbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:fingerprint-filled" {...props}></Icon>
