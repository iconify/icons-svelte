<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_a6-pb4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k_a6-pb4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:aspect-ratio-line" {...props}></Icon>
