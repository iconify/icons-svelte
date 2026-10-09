<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxvnz_b5x.css';
import '../../css/q/qgo3qub9a.css';
import '../../css/l/lj93my_zy.css';
import '../../css/r/ryz6tf6qj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="uxvnz_b5x"/><path class="qgo3qub9a"/><path class="lj93my_zy"/><path class="ryz6tf6qj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:house-key-48-bold" {...props}></Icon>
