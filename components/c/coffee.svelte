<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bocd00ptt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bocd00ptt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:coffee" {...props}></Icon>
