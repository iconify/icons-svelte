<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pct_djbqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pct_djbqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:copper-diamond-fill" {...props}></Icon>
