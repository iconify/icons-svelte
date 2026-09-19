<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdmuq9b0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="jdmuq9b0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:picture" {...props}></Icon>
