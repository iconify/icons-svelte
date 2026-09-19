<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz0bikexj.css';
import '../../css/a/an2--ubjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nz0bikexj"/><path class="an2--ubjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:border-outer" {...props}></Icon>
