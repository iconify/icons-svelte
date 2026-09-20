<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bni1lgbxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bni1lgbxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:moon-waxing-crescent" {...props}></Icon>
