<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/np1z57bvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="np1z57bvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:open-a-i-filled" {...props}></Icon>
