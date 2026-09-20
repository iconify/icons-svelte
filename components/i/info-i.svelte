<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ks7rzvckl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ks7rzvckl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:info-i" {...props}></Icon>
