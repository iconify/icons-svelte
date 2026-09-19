<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i70wu6boj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i70wu6boj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ceiling-fair-semiflush" {...props}></Icon>
