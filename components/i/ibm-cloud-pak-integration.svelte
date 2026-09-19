<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqfy9bbax.css';
import '../../css/m/mol3e-blu.css';
import '../../css/f/f86xz6sdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sqfy9bbax"/><path class="mol3e-blu"/><path class="f86xz6sdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-cloud-pak-integration" {...props}></Icon>
