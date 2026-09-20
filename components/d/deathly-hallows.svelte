<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_2s7obvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o_2s7obvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:deathly-hallows" {...props}></Icon>
