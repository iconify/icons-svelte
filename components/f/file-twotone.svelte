<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ux_5wvris.css';
import '../../css/j/jso3jy2en.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ux_5wvris"/><path class="jso3jy2en"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:file-twotone" {...props}></Icon>
