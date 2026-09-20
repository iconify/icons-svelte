<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ttpvcybxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ttpvcybxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:pie-chart-line" {...props}></Icon>
