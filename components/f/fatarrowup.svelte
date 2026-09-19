<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-j074bag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1023};
const content = `<path class="e-j074bag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:fatarrowup" {...props}></Icon>
