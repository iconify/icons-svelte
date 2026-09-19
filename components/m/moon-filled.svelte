<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kwzgucc_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="kwzgucc_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:moon-filled" {...props}></Icon>
