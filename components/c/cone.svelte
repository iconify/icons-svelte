<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0_6e3iib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="o0_6e3iib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:cone" {...props}></Icon>
