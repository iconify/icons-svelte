<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p8p_gac5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p8p_gac5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:control-value-bar" {...props}></Icon>
