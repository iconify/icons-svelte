<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxjqujbwc.css';
import '../../css/l/l1832ablw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fxjqujbwc"/><path class="l1832ablw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:radiator-48-bold" {...props}></Icon>
