<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wilbl5bnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="wilbl5bnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:out-of-office" {...props}></Icon>
