<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gtx0be1eg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="gtx0be1eg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:gemini-filled" {...props}></Icon>
