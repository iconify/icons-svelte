<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uyi6f9bda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="uyi6f9bda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:file-sync" {...props}></Icon>
