<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bg7k6vike.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bg7k6vike"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:circle-with-vertical-bar" {...props}></Icon>
