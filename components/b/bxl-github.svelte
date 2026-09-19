<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvrho5bdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hvrho5bdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-github" {...props}></Icon>
