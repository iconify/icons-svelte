<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nco9j1bhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="nco9j1bhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:printer-fill" {...props}></Icon>
