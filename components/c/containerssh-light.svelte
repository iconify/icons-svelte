<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pw2k4fb0y.css';
import '../../css/d/d5-tlybrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pw2k4fb0y"/><path class="d5-tlybrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:containerssh-light" {...props}></Icon>
