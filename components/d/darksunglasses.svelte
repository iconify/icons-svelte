<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2w7w-b-w.css';
import '../../css/q/q49xs08qd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z2w7w-b-w"/><path class="q49xs08qd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:darksunglasses" {...props}></Icon>
