<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zpm3-ysuq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="zpm3-ysuq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:downdouble" {...props}></Icon>
