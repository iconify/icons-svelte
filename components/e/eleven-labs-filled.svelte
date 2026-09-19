<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3jb4gb8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="j3jb4gb8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:eleven-labs-filled" {...props}></Icon>
