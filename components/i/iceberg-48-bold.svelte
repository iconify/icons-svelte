<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccy8rfxnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ccy8rfxnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:iceberg-48-bold" {...props}></Icon>
