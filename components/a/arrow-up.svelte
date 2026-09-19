<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbw0lvbdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wbw0lvbdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:arrow-up" {...props}></Icon>
