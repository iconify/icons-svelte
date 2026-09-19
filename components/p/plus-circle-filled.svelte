<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bq50plqvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="bq50plqvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:plus-circle-filled" {...props}></Icon>
