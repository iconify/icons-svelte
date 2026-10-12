<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7c8n5bpv.css';
import '../../css/o/obndhi7my.css';
import '../../css/i/itu66bbfs.css';
import '../../css/f/f2mixfbea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="y7c8n5bpv"/><path class="obndhi7my"/><path class="itu66bbfs"/><path class="f2mixfbea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gem-20" {...props}></Icon>
