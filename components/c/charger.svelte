<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvxqpcc6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="zvxqpcc6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:charger" {...props}></Icon>
