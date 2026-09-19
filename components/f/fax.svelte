<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bq5k6h_1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bq5k6h_1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:fax" {...props}></Icon>
