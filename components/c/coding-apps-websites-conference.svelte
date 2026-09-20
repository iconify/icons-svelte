<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwpb1xudv.css';
import '../../css/f/f-bnc8bnz.css';
import '../../css/u/um4v6ab4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mwpb1xudv"/><path class="f-bnc8bnz"/><path class="um4v6ab4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:coding-apps-websites-conference" {...props}></Icon>
