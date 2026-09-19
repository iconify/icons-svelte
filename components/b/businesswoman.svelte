<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zw33xtbeb.css';
import '../../css/u/uopwe8brh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zw33xtbeb"/><path class="uopwe8brh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:businesswoman" {...props}></Icon>
