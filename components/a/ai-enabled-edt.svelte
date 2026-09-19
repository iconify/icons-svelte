<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_sdgxrgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="b_sdgxrgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ai-enabled-edt" {...props}></Icon>
