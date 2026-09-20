<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tl6d73b_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tl6d73b_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:colour-tuning-bold" {...props}></Icon>
