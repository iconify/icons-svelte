<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dssr3rb_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dssr3rb_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-rectangle" {...props}></Icon>
