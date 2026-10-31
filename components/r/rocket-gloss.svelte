<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gm1ipct2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gm1ipct2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:rocket-gloss" {...props}></Icon>
