<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ha61aebhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ha61aebhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:api-fill" {...props}></Icon>
