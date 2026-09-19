<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y2m5zi2on.css';
import '../../css/y/yadluib6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="y2m5zi2on"/><path class="yadluib6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-ibv" {...props}></Icon>
