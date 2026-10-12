<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ha7298_1d.css';
import '../../css/w/wieaolbut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ha7298_1d"/><path class="wieaolbut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:password-20" {...props}></Icon>
