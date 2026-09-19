<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfi0w_2co.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bfi0w_2co"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:add-keyframe-alt" {...props}></Icon>
