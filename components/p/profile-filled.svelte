<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrl9hab2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="yrl9hab2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:profile-filled" {...props}></Icon>
