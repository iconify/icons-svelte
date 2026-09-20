<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ylt94hh4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ylt94hh4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-excel-fill" {...props}></Icon>
