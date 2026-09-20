<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9jr-rb2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="c9jr-rb2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:a-frame-sidewall-tents" {...props}></Icon>
