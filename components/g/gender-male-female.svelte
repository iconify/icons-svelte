<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nfqqq2-qh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nfqqq2-qh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:gender-male-female" {...props}></Icon>
