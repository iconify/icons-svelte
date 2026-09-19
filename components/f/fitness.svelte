<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vr1sutbfj.css';
import '../../css/l/ll09ir12a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vr1sutbfj"/><path class="ll09ir12a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:fitness" {...props}></Icon>
