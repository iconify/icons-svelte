<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-4ux5-sz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="g-4ux5-sz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:import-outline" {...props}></Icon>
