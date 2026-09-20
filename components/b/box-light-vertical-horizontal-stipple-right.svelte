<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/slc0ckb5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="slc0ckb5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-vertical-horizontal-stipple-right" {...props}></Icon>
