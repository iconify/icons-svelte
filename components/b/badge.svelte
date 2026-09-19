<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iaj3ch19q.css';
import '../../css/l/lj_w3s1cd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="iaj3ch19q"/><path class="lj_w3s1cd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:badge" {...props}></Icon>
