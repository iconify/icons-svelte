<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/re4n0ebks.css';
import '../../css/a/a01wef02w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="re4n0ebks"/><path class="a01wef02w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:people-heart" {...props}></Icon>
