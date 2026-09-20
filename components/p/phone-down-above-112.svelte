<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zo01rrp1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zo01rrp1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:phone-down-above-112" {...props}></Icon>
