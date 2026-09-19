<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-t7wxb1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="b-t7wxb1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:account-browser" {...props}></Icon>
