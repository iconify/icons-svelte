<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rv0s7yb0o.css';
import '../../css/d/da9g56non.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="rv0s7yb0o"/><path class="da9g56non"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hetzner" {...props}></Icon>
