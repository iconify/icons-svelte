<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bt1x3tsxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bt1x3tsxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:k21" {...props}></Icon>
