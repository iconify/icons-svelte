<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t1tqccbrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t1tqccbrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:e-bike-2" {...props}></Icon>
