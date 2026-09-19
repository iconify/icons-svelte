<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g67g2gbzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="g67g2gbzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:file-jpg" {...props}></Icon>
