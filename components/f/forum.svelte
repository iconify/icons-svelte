<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/inr2iybus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="inr2iybus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:forum" {...props}></Icon>
