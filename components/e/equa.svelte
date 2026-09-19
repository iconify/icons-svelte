<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_1hf_bfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="k_1hf_bfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:equa" {...props}></Icon>
