<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ln0oe0zwr.css';
import '../../css/c/crznqgb3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":25};
const content = `<path class="ln0oe0zwr"/><path class="crznqgb3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:exit-up" {...props}></Icon>
