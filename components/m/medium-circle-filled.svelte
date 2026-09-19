<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jy1d9zbpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="jy1d9zbpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:medium-circle-filled" {...props}></Icon>
