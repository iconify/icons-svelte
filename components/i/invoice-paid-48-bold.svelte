<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zryaw4dka.css';
import '../../css/m/mxfeqjd4c.css';
import '../../css/y/y9mg2tbzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zryaw4dka"/><path class="mxfeqjd4c"/><path class="y9mg2tbzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:invoice-paid-48-bold" {...props}></Icon>
