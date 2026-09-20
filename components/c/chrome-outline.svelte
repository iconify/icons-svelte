<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jb0yl91bu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jb0yl91bu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:chrome-outline" {...props}></Icon>
