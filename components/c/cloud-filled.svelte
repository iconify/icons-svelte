<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3jxwfbha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="p3jxwfbha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:cloud-filled" {...props}></Icon>
