<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3ouhtb3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="q3ouhtb3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:ellipse-outline" {...props}></Icon>
