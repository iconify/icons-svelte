<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eftem4_0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eftem4_0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:code-sparkle-fill-round" {...props}></Icon>
