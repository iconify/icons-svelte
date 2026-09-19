<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbep0udnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tbep0udnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-bluetooth" {...props}></Icon>
