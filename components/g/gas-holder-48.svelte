<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yr5mp9iol.css';
import '../../css/m/mw4tppx2s.css';
import '../../css/c/c65-ehvfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yr5mp9iol"/><path class="mw4tppx2s"/><path class="c65-ehvfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gas-holder-48" {...props}></Icon>
