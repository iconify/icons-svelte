<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_vbgsb4a.css';
import '../../css/e/e4z-0xbtc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="o_vbgsb4a"/><path class="e4z-0xbtc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:baby-20" {...props}></Icon>
