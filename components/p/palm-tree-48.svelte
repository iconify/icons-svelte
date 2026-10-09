<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqeig8tmv.css';
import '../../css/x/xwmv3qb7e.css';
import '../../css/t/t3xeeshqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hqeig8tmv"/><path class="xwmv3qb7e"/><path class="t3xeeshqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:palm-tree-48" {...props}></Icon>
