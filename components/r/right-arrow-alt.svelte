<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/em2d4achx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="em2d4achx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:right-arrow-alt" {...props}></Icon>
