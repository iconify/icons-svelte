<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tyrmry45n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tyrmry45n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:comment-sharp" {...props}></Icon>
