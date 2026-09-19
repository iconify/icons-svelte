<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uaebsod0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="uaebsod0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:file-zip-fill" {...props}></Icon>
