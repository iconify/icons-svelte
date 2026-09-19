<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkm6zyj7x.css';
import '../../css/i/idjmobcht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jkm6zyj7x"/><path class="idjmobcht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:basket-sharp" {...props}></Icon>
