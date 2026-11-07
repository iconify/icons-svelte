<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mp600_i4z.css';
import '../../css/o/osemxebgc.css';
import '../../css/j/jy0yf6bpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mp600_i4z"/><path clip-rule="evenodd" class="osemxebgc"/><path class="jy0yf6bpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:battery-charge-minimalistic-outline" {...props}></Icon>
