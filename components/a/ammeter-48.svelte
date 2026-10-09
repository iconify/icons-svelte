<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndoo8eizj.css';
import '../../css/h/h7ne39bmg.css';
import '../../css/z/z0k_6w9gl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ndoo8eizj"/><path class="h7ne39bmg"/><path class="z0k_6w9gl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ammeter-48" {...props}></Icon>
