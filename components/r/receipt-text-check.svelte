<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-hh5tbqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k-hh5tbqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:receipt-text-check" {...props}></Icon>
