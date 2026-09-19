<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sf1c1hbcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="sf1c1hbcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:delete-rows" {...props}></Icon>
