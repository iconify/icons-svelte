<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gik1z9cpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="gik1z9cpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:ellipsis-outline" {...props}></Icon>
