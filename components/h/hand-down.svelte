<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7d5zs9qk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t7d5zs9qk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:hand-down" {...props}></Icon>
