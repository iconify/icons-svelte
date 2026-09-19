<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ud5onibxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1023};
const content = `<path class="ud5onibxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:downleft" {...props}></Icon>
