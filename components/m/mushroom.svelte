<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/islpwrbax.css';
import '../../css/f/fg_9inbkk.css';
import '../../css/g/g1vushbzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="islpwrbax"/><path class="fg_9inbkk"/><path class="g1vushbzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:mushroom" {...props}></Icon>
