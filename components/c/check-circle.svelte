<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbh8_acgb.css';
import '../../css/g/gd6ueob5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fbh8_acgb"/><path class="gd6ueob5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:check-circle" {...props}></Icon>
