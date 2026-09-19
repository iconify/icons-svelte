<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozfohubwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ozfohubwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:font-colors-outlined" {...props}></Icon>
