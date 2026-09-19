<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ml9_4kbao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ml9_4kbao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:prototools" {...props}></Icon>
