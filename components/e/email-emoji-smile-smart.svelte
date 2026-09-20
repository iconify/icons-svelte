<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqpbdh_ni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mqpbdh_ni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:email-emoji-smile-smart" {...props}></Icon>
