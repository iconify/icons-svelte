<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvof47lrw.css';
import '../../css/j/jtcikdbak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="tvof47lrw"/><path class="jtcikdbak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:api-twotone" {...props}></Icon>
