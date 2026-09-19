<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbk2lq5ev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":416,"height":504};
const content = `<path class="wbk2lq5ev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:quora" {...props}></Icon>
