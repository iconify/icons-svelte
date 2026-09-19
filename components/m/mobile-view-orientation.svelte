<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hkwnyu5zy.css';
import '../../css/o/onqnis1mn.css';
import '../../css/h/h6hpqtbrt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hkwnyu5zy"/><path class="onqnis1mn"/><path class="h6hpqtbrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:mobile-view-orientation" {...props}></Icon>
