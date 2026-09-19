<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7mwa9bbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="z7mwa9bbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:code-sandbox-square" {...props}></Icon>
