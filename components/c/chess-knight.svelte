<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zi_zl8bpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="zi_zl8bpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:chess-knight" {...props}></Icon>
