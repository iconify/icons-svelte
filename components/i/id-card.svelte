<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fl-ou4joe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="fl-ou4joe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:id-card" {...props}></Icon>
