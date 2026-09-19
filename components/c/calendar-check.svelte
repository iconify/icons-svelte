<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxkm_rblg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hxkm_rblg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:calendar-check" {...props}></Icon>
