<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ma2qfxbce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ma2qfxbce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chevrons-up-down-48-bold" {...props}></Icon>
