<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vj49qk69z.css';
import '../../css/n/nq27wzbeg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vj49qk69z"/><path class="nq27wzbeg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:keyboard-20-bold" {...props}></Icon>
