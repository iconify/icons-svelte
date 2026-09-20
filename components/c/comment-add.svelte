<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jp28u69ws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jp28u69ws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:comment-add" {...props}></Icon>
