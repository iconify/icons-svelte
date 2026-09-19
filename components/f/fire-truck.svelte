<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yy6mcej6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yy6mcej6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:fire-truck" {...props}></Icon>
