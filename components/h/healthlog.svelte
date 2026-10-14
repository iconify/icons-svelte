<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nue79bcyt.css';
import '../../css/k/k237ps8_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nue79bcyt"/><path class="k237ps8_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:healthlog" {...props}></Icon>
