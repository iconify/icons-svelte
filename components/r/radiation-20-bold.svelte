<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_-yre08v.css';
import '../../css/z/z74qi6bgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p_-yre08v"/><path class="z74qi6bgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:radiation-20-bold" {...props}></Icon>
