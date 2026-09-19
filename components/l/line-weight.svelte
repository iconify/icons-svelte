<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3a2tccdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g3a2tccdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:line-weight" {...props}></Icon>
