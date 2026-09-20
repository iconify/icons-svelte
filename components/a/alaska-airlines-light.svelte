<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wtw1qacud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wtw1qacud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:alaska-airlines-light" {...props}></Icon>
