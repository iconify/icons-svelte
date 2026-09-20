<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hj72zb1uq.css';
import '../../css/t/tp29nr70i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hj72zb1uq"/><path class="tp29nr70i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:feed-tag-16" {...props}></Icon>
