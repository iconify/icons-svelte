<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8_9rfgus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l8_9rfgus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:dots-3x3" {...props}></Icon>
