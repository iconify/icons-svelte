<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/orc8djbsy.css';
import '../../css/s/s5lw05brm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="orc8djbsy"/><path class="s5lw05brm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-trash" {...props}></Icon>
