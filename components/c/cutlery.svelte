<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zndc0hg1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zndc0hg1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:cutlery" {...props}></Icon>
