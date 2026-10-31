<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d49mp3bjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d49mp3bjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:gold-ingot-gloss" {...props}></Icon>
