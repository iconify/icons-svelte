<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8g1rbcqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="z8g1rbcqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:braces" {...props}></Icon>
