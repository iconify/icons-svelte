<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbnco8jkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vbnco8jkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:building-up" {...props}></Icon>
