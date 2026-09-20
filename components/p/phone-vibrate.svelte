<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7_4w1gdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x7_4w1gdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:phone-vibrate" {...props}></Icon>
