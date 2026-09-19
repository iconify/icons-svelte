<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jq0upff5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="jq0upff5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:paperclip-12" {...props}></Icon>
