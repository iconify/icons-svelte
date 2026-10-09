<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbl-5-buj.css';
import '../../css/v/v101e1bjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tbl-5-buj"/><path class="v101e1bjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hash-48-bold" {...props}></Icon>
