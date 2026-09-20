<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dm0i6fb7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dm0i6fb7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:five-minus" {...props}></Icon>
