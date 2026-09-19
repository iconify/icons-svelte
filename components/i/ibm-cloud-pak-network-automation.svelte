<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpxwy_jwh.css';
import '../../css/k/kqmlytbco.css';
import '../../css/m/mw99uy5ni.css';
import '../../css/f/f86xz6sdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wpxwy_jwh"/><path class="kqmlytbco"/><path class="mw99uy5ni"/><path class="f86xz6sdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-cloud-pak-network-automation" {...props}></Icon>
