<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qp0akibsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qp0akibsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-excel-2-fill" {...props}></Icon>
