<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0tm3lyhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c0tm3lyhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:backwithleftwardsarrow" {...props}></Icon>
