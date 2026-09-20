<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/osu97bcqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="osu97bcqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:religion-cross-1-religion-cross-culture-bold" {...props}></Icon>
