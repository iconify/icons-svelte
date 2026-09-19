<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjbsh1btt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yjbsh1btt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:circle-fading-arrow-up" {...props}></Icon>
