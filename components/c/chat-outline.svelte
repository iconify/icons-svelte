<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cws_mosnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cws_mosnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:chat-outline" {...props}></Icon>
