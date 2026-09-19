<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lx0on2fza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lx0on2fza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-minus-circle" {...props}></Icon>
