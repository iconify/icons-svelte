<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zj-5oz67e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zj-5oz67e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:hospital-sign-square-remix" {...props}></Icon>
