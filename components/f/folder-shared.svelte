<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_t41-uxm.css';
import '../../css/s/sx1789nbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="g_t41-uxm"/><path class="sx1789nbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-shared" {...props}></Icon>
