<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ca5ull6cn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ca5ull6cn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:code-standards" {...props}></Icon>
