<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j648mcboz.css';
import '../../css/i/iiv7b4kfn.css';
import '../../css/j/jggsly9mc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="j648mcboz"/><path class="iiv7b4kfn"/><path class="jggsly9mc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:colombia" {...props}></Icon>
