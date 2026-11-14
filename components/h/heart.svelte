<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxkfidbmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lxkfidbmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:heart" {...props}></Icon>
