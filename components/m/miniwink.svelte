<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-cf82kwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":896};
const content = `<path class="s-cf82kwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:miniwink" {...props}></Icon>
