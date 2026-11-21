<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvt1q9bhv.css';
import '../../css/j/jp9nm159y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lvt1q9bhv"/><path class="jp9nm159y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:hand-left-outline" {...props}></Icon>
