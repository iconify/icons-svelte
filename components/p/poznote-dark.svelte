<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mifldab4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mifldab4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:poznote-dark" {...props}></Icon>
