<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgm81wbny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zgm81wbny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:hexagon-letter-i-filled" {...props}></Icon>
