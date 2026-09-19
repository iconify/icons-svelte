<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q__y2nbzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q__y2nbzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:badge" {...props}></Icon>
