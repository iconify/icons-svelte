<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yc7iu5jzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="yc7iu5jzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:parameter" {...props}></Icon>
