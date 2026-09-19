<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgeh2rblg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":634};
const content = `<path class="wgeh2rblg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:comments" {...props}></Icon>
