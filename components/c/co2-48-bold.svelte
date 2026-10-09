<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bpcie8_sa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bpcie8_sa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:co2-48-bold" {...props}></Icon>
