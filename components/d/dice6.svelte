<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aaucvf-bc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="aaucvf-bc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:dice6" {...props}></Icon>
