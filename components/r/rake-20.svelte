<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/td9q1sb4m.css';
import '../../css/r/r74_arb3k.css';
import '../../css/m/m-5l6lb7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="td9q1sb4m"/><path class="r74_arb3k"/><path class="m-5l6lb7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rake-20" {...props}></Icon>
