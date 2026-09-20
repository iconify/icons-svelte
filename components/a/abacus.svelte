<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umx1wmpnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="umx1wmpnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:abacus" {...props}></Icon>
