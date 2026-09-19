<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ryi47hrkh.css';
import '../../css/h/h41dyrd2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ryi47hrkh"/><path class="h41dyrd2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bookmarks" {...props}></Icon>
