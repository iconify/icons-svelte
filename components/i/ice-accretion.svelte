<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esl9wpbmj.css';
import '../../css/h/haitiqbis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="esl9wpbmj"/><path class="haitiqbis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ice-accretion" {...props}></Icon>
