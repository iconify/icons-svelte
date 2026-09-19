<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwn1zdb8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qwn1zdb8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:bluetooth" {...props}></Icon>
