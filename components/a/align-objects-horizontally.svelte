<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lc7a14f7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lc7a14f7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:align-objects-horizontally" {...props}></Icon>
