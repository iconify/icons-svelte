<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gur1qyx5l.css';
import '../../css/q/qag32gbsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gur1qyx5l"/><path class="qag32gbsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:event-warning" {...props}></Icon>
