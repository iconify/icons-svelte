<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzvic1rda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jzvic1rda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:pencil-alt-fill-round" {...props}></Icon>
