<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/haxprhbvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="haxprhbvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:blood-bank-15" {...props}></Icon>
