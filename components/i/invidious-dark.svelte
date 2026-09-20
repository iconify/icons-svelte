<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pyhnag69p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pyhnag69p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:invidious-dark" {...props}></Icon>
