<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1oyp4uhi.css';
import '../../css/q/qyfd5ps_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="b1oyp4uhi"/><path class="qyfd5ps_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:calculator-20" {...props}></Icon>
