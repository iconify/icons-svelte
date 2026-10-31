<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l2xtnil3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l2xtnil3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:menu-double-large-fill-round" {...props}></Icon>
