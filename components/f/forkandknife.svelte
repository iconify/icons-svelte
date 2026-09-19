<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/he60vhbyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="he60vhbyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:forkandknife" {...props}></Icon>
