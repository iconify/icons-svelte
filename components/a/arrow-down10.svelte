<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfnwd7b7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xfnwd7b7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:arrow-down10" {...props}></Icon>
