<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgi3klbbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="hgi3klbbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:message-outlined" {...props}></Icon>
