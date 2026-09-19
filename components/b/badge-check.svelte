<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ose1jpb8n.css';
import '../../css/h/hfzh1ebhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ose1jpb8n"/><path class="hfzh1ebhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:badge-check" {...props}></Icon>
