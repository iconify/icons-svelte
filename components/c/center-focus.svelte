<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/do3z1_b6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="do3z1_b6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:center-focus" {...props}></Icon>
