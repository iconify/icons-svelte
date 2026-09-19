<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tz-xk656g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="tz-xk656g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:numbered-list-number" {...props}></Icon>
