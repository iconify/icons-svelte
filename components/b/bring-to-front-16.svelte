<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qy9w8ibxy.css';
import '../../css/a/a_0finyys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qy9w8ibxy"/><path class="a_0finyys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:bring-to-front-16" {...props}></Icon>
