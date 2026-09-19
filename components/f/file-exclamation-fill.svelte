<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/azei6ab0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="azei6ab0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:file-exclamation-fill" {...props}></Icon>
