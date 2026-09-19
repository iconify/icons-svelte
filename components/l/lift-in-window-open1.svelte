<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-a25uhrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u-a25uhrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:lift-in-window-open1" {...props}></Icon>
