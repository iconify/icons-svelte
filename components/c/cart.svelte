<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yxr6ncb7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yxr6ncb7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:cart" {...props}></Icon>
