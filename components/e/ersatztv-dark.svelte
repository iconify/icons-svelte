<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htwi9xkgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="htwi9xkgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ersatztv-dark" {...props}></Icon>
