<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_zpkg6wi.css';
import '../../css/u/uwggcevzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="o_zpkg6wi"/><path class="uwggcevzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:doorbell-48-bold" {...props}></Icon>
