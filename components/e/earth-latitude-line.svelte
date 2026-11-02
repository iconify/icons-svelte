<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ke28dhbov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ke28dhbov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:earth-latitude-line" {...props}></Icon>
