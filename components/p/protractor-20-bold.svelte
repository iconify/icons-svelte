<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lehxztmwm.css';
import '../../css/r/r_0sobc6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lehxztmwm"/><path class="r_0sobc6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:protractor-20-bold" {...props}></Icon>
