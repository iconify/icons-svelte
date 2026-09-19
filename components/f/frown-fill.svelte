<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhxhmzp8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="nhxhmzp8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:frown-fill" {...props}></Icon>
