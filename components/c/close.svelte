<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2-u81xmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s2-u81xmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:close" {...props}></Icon>
