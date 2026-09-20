<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v8n35mg7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v8n35mg7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:mix" {...props}></Icon>
