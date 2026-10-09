<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/diqsj_bxu.css';
import '../../css/g/g0orui1mh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="diqsj_bxu"/><path class="g0orui1mh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:drought-48-bold" {...props}></Icon>
