<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y2qs83soi.css';
import '../../css/e/ea7_acb9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y2qs83soi"/><path class="ea7_acb9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-history" {...props}></Icon>
