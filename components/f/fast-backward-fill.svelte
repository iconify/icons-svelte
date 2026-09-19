<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ce2gzmb0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ce2gzmb0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:fast-backward-fill" {...props}></Icon>
