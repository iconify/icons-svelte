<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcv3g-l2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="pcv3g-l2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-down-square-fill" {...props}></Icon>
