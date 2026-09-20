<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i76hc9b2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i76hc9b2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:home-9-fill" {...props}></Icon>
