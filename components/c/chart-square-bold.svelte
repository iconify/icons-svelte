<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wk8-a8pgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wk8-a8pgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chart-square-bold" {...props}></Icon>
