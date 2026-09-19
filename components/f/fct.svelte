<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_nrhxj7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q_nrhxj7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:fct" {...props}></Icon>
