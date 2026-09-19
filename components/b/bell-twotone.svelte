<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1b1abbxl.css';
import '../../css/e/eoz47dboi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="j1b1abbxl"/><path class="eoz47dboi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:bell-twotone" {...props}></Icon>
