<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-lwsub9k.css';
import '../../css/e/e3net-b-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l-lwsub9k"/><path class="e3net-b-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:heartblue" {...props}></Icon>
