<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlcn6fb6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="mlcn6fb6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:contraceptive-diaphragm" {...props}></Icon>
