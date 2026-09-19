<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxvborn7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qxvborn7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:flame" {...props}></Icon>
