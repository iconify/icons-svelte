<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bn58tbcdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="bn58tbcdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:check" {...props}></Icon>
