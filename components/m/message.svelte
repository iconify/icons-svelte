<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eq3vk_b1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="eq3vk_b1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:message" {...props}></Icon>
