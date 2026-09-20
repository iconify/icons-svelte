<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z22ilujae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="z22ilujae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:harmonix" {...props}></Icon>
