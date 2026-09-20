<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-kbtesqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="a-kbtesqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:life-ring" {...props}></Icon>
