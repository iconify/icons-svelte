<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fn7jf3uuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="fn7jf3uuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:123-fill-12" {...props}></Icon>
