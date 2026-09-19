<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iy3tuvb_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iy3tuvb_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:compress-right" {...props}></Icon>
