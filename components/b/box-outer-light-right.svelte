<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qh2n0hprc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="qh2n0hprc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-outer-light-right" {...props}></Icon>
