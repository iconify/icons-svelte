<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4kpq-8ui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z4kpq-8ui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:minus" {...props}></Icon>
