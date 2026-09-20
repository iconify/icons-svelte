<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_t41-uxm.css';
import '../../css/c/c6y61i2ho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="g_t41-uxm"/><path class="c6y61i2ho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-simulations" {...props}></Icon>
