<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgspd8b2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sgspd8b2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:close" {...props}></Icon>
