<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ax1am94cr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ax1am94cr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:bookmark" {...props}></Icon>
