<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6eu_k3xl.css';
import '../../css/f/f9l75pbbf.css';
import '../../css/q/q736ljmrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="g6eu_k3xl"/><path class="f9l75pbbf"/><path class="q736ljmrr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:carbon-offset-48-bold" {...props}></Icon>
