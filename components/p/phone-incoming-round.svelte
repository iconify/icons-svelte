<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ix5wi_6hb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ix5wi_6hb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:phone-incoming-round" {...props}></Icon>
