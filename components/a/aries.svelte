<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqfm60b_p.css';
import '../../css/h/hrtye35bf.css';
import '../../css/d/d-v18x27r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qqfm60b_p"/><path class="hrtye35bf"/><path class="d-v18x27r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:aries" {...props}></Icon>
