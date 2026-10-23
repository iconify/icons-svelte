<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oz9bkmbkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oz9bkmbkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:file-pen" {...props}></Icon>
