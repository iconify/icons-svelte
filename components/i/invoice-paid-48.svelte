<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crpcihb-l.css';
import '../../css/k/k1v5xj0bd.css';
import '../../css/z/z4sj3ixdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="crpcihb-l"/><path class="k1v5xj0bd"/><path class="z4sj3ixdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:invoice-paid-48" {...props}></Icon>
