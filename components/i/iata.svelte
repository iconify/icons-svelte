<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xz_zxo7ox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xz_zxo7ox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:iata" {...props}></Icon>
