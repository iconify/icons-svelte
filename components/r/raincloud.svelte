<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_7l6fcgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k_7l6fcgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:raincloud" {...props}></Icon>
