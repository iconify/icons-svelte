<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kco8tpa1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kco8tpa1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:caret-down-circle" {...props}></Icon>
