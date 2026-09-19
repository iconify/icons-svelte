<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tf7dcjbes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="tf7dcjbes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:angellist" {...props}></Icon>
