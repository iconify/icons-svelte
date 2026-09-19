<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjcm6d98u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="zjcm6d98u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:discord-outlined" {...props}></Icon>
