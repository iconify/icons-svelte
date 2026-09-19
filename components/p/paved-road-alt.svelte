<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvzp7_oqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="rvzp7_oqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:paved-road-alt" {...props}></Icon>
