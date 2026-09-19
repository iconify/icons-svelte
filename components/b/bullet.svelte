<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wtxu6e6hc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="wtxu6e6hc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:bullet" {...props}></Icon>
