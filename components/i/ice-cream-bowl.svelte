<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b47e4sbey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b47e4sbey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:ice-cream-bowl" {...props}></Icon>
