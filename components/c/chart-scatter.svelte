<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kx6aa2bte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kx6aa2bte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:chart-scatter" {...props}></Icon>
