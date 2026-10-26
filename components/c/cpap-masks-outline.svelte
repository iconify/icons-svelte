<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oso_04bvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="oso_04bvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:cpap-masks-outline" {...props}></Icon>
