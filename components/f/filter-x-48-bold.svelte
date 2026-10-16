<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oi2mxu8vr.css';
import '../../css/e/e1wjloqot.css';
import '../../css/z/zd51tnb1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="oi2mxu8vr"/><path class="e1wjloqot"/><path class="zd51tnb1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:filter-x-48-bold" {...props}></Icon>
