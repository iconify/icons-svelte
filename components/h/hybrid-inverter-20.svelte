<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hi5qd16vh.css';
import '../../css/v/v7zpq2cvm.css';
import '../../css/o/o76juu94h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hi5qd16vh"/><path class="v7zpq2cvm"/><path class="o76juu94h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hybrid-inverter-20" {...props}></Icon>
