<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/og4jt_bra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="og4jt_bra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:flag" {...props}></Icon>
