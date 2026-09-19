<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/om6z7p6bj.css';
import '../../css/d/dy3-7pbwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="om6z7p6bj"/><path class="dy3-7pbwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:ma-1x1" {...props}></Icon>
