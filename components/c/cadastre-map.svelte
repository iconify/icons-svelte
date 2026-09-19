<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/st95u1bne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="st95u1bne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:cadastre-map" {...props}></Icon>
