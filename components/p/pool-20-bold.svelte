<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofsojfsnm.css';
import '../../css/q/q45btnm6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ofsojfsnm"/><path class="q45btnm6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pool-20-bold" {...props}></Icon>
