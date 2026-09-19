<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvdvxcbwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="mvdvxcbwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:caret-bottom" {...props}></Icon>
