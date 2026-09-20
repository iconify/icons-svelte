<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtowsomii.css';
import '../../css/d/d-8w03bro.css';
import '../../css/h/hrjfpsb2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<g transform="translate(4 2)" class="jtowsomii"><path class="d-8w03bro"/><circle class="hrjfpsb2u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:location" {...props}></Icon>
