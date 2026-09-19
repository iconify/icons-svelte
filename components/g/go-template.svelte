<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/duddcrv6n.css';
import '../../css/k/koyzp3bls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="duddcrv6n"/><path class="koyzp3bls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:go-template" {...props}></Icon>
