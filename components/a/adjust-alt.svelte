<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqsh6n6fl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="oqsh6n6fl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:adjust-alt" {...props}></Icon>
