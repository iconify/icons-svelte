<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nirzt8hqp.css';
import '../../css/k/kite7abkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nirzt8hqp"/><path class="kite7abkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:image-sparkle-20-bold" {...props}></Icon>
