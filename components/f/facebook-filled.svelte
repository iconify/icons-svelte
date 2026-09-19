<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/liy6tw56v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="liy6tw56v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:facebook-filled" {...props}></Icon>
