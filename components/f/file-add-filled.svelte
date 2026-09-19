<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8t1wibbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="u8t1wibbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:file-add-filled" {...props}></Icon>
