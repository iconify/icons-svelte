<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfla53asp.css';
import '../../css/w/w67qn2bfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zfla53asp"/><path class="w67qn2bfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-code-working" {...props}></Icon>
