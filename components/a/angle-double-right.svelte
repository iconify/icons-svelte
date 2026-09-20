<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ny6k_kb5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ny6k_kb5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:angle-double-right" {...props}></Icon>
