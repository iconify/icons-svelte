<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qs3s_acpz.css';
import '../../css/c/c36ktfb4d.css';
import '../../css/l/l5cqi8bbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qs3s_acpz"/><path class="c36ktfb4d"/><path class="l5cqi8bbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:circular-saw-20" {...props}></Icon>
