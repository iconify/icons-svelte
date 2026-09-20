<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uh2_e72fr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="uh2_e72fr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:cotton-bureau" {...props}></Icon>
