<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2w8fkt6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="w2w8fkt6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:phone-down-above-123" {...props}></Icon>
