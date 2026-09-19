<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3-vaeb_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q3-vaeb_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:flip-vertical-filled" {...props}></Icon>
