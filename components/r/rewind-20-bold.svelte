<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q06plnibn.css';
import '../../css/b/bb-6nmboa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="q06plnibn"/><path class="bb-6nmboa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rewind-20-bold" {...props}></Icon>
