<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8ilg030l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u8ilg030l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:minimize-gloss" {...props}></Icon>
