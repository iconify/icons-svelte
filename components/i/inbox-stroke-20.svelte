<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mn1v_kase.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mn1v_kase"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:inbox-stroke-20" {...props}></Icon>
