<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/axbb0qx1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="axbb0qx1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:phone-down-above-one-one-one" {...props}></Icon>
