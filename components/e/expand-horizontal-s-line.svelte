<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yy_6qlgcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yy_6qlgcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:expand-horizontal-s-line" {...props}></Icon>
