<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aw5x8425k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aw5x8425k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:key" {...props}></Icon>
