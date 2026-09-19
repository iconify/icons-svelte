<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ik48zub3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ik48zub3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:credit-card" {...props}></Icon>
