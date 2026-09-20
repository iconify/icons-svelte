<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4d4uacpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="k4d4uacpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:arrow-move-flat" {...props}></Icon>
