<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1l1qmjew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q1l1qmjew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:leftthoughtbubble" {...props}></Icon>
