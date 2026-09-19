<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwfiues2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bwfiues2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:flag-1" {...props}></Icon>
