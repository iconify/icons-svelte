<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9s0-fbjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b9s0-fbjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:bookmark-off-round" {...props}></Icon>
