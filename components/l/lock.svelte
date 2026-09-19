<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrw_4kbwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":32};
const content = `<path class="zrw_4kbwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:lock" {...props}></Icon>
