<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9uroy2xg.css';
import '../../css/x/xso8lt60u.css';
import '../../css/f/f0tp4idyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="e9uroy2xg"/><path class="xso8lt60u"/><path class="f0tp4idyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:filter-x-20-bold" {...props}></Icon>
