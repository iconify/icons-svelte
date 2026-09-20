<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztddpjf-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ztddpjf-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:bit-coin-fill" {...props}></Icon>
