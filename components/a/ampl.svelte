<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rw659x9es.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rw659x9es"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:ampl" {...props}></Icon>
