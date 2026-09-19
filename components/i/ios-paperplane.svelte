<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhvnz9bwg.css';
import '../../css/s/soter0kom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hhvnz9bwg"/><path class="soter0kom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-paperplane" {...props}></Icon>
