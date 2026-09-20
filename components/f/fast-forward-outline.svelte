<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8xpqxbbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o8xpqxbbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:fast-forward-outline" {...props}></Icon>
