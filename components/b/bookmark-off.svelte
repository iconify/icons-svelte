<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqg76lbju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iqg76lbju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:bookmark-off" {...props}></Icon>
