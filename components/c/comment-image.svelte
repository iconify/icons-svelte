<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmcb4ub3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bmcb4ub3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:comment-image" {...props}></Icon>
