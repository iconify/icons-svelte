<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2_6f6b7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="m2_6f6b7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:reddit-square-fill" {...props}></Icon>
