<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_xpt5bbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":833};
const content = `<path class="e_xpt5bbt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:flowdown" {...props}></Icon>
