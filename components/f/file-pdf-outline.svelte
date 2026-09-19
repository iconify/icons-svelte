<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzny27bve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="tzny27bve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:file-pdf-outline" {...props}></Icon>
