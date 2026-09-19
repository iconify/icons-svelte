<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/li570cb7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="li570cb7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:chevron-left-circle" {...props}></Icon>
