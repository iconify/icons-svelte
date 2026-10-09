<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzp1g281f.css';
import '../../css/c/crfyh3bij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mzp1g281f"/><path class="crfyh3bij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:dice-4-48-bold" {...props}></Icon>
