<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0m87kb6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="z0m87kb6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:facebook" {...props}></Icon>
