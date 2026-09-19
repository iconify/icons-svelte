<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0lsn2zoo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1026};
const content = `<path class="n0lsn2zoo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:arrowleft" {...props}></Icon>
