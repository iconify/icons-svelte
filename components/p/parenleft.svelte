<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e4i38ybpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":182,"height":981};
const content = `<path class="e4i38ybpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:parenleft" {...props}></Icon>
