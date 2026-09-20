<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3claz1-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x3claz1-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:email-minus-outline" {...props}></Icon>
