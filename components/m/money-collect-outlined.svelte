<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omviflb8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="omviflb8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:money-collect-outlined" {...props}></Icon>
