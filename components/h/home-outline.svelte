<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j72nmtz-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="j72nmtz-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:home-outline" {...props}></Icon>
