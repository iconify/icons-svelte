<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctgsm2yze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ctgsm2yze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:checkbox-component-mixed" {...props}></Icon>
