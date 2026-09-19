<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vpzed0b9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":768};
const content = `<path class="vpzed0b9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:hdvideo" {...props}></Icon>
