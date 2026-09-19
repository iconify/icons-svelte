<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mg6d2vd4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mg6d2vd4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:play-skip-back" {...props}></Icon>
