<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6w4ul_vh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":527,"height":735};
const content = `<path class="q6w4ul_vh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:h-upper-case" {...props}></Icon>
