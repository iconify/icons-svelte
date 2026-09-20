<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eiqj4rbas.css';
import '../../css/z/z0v3o5vsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eiqj4rbas"/><path class="z0v3o5vsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:openprinting-cups" {...props}></Icon>
