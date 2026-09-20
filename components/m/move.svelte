<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwpciib6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="lwpciib6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:move" {...props}></Icon>
