<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5d19acce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x5d19acce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:pen-nib" {...props}></Icon>
