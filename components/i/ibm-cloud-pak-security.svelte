<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l6wondblj.css';
import '../../css/f/f86xz6sdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="l6wondblj"/><path class="f86xz6sdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-cloud-pak-security" {...props}></Icon>
