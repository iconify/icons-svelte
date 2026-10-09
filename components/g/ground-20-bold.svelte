<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0ezl7eqf.css';
import '../../css/m/mgkn3accm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="i0ezl7eqf"/><path class="mgkn3accm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ground-20-bold" {...props}></Icon>
