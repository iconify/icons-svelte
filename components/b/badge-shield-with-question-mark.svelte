<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/do_ni8ani.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="do_ni8ani"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:badge-shield-with-question-mark" {...props}></Icon>
