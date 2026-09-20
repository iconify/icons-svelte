<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvn4_zbbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="rvn4_zbbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bear-spray-can-with-spray-and-yen-yuan" {...props}></Icon>
