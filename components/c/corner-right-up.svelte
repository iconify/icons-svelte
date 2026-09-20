<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kw8kqht8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kw8kqht8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:corner-right-up" {...props}></Icon>
