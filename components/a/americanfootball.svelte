<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r1kfkvbcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="r1kfkvbcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:americanfootball" {...props}></Icon>
