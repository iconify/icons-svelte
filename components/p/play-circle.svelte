<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wrqeixy1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wrqeixy1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:play-circle" {...props}></Icon>
