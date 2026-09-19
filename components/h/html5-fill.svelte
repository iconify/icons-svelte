<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfy7vkm7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="gfy7vkm7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:html5-fill" {...props}></Icon>
