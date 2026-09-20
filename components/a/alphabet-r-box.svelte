<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvuexqv9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kvuexqv9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:alphabet-r-box" {...props}></Icon>
