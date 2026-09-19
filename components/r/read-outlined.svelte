<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lef8gbbzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="lef8gbbzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:read-outlined" {...props}></Icon>
