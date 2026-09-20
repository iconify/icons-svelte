<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wb1hd8b6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="wb1hd8b6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:accounting" {...props}></Icon>
