<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/px1bfwbyg.css';
import '../../css/x/xblgcabps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="px1bfwbyg"/><path class="xblgcabps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:facebook-messenger-alt" {...props}></Icon>
