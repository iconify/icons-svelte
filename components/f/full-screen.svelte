<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6uqneswq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="u6uqneswq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:full-screen" {...props}></Icon>
