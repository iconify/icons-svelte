<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c70yz9b3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="c70yz9b3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:mobile-event" {...props}></Icon>
