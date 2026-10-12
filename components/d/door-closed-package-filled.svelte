<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iq0ba4bnx.css';
import '../../css/f/fu6wn7bkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iq0ba4bnx"/><path class="fu6wn7bkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:door-closed-package-filled" {...props}></Icon>
