<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lh9m-lbrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lh9m-lbrr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:hand-pointing-right-01" {...props}></Icon>
