<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hq_u29btb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hq_u29btb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:power-la" {...props}></Icon>
