<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/znhln2gbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="znhln2gbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:file-excel-outlined" {...props}></Icon>
