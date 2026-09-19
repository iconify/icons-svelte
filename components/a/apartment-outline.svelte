<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dd4pmb2eb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="dd4pmb2eb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:apartment-outline" {...props}></Icon>
