<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgurgy0cl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="jgurgy0cl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:appstore-filled" {...props}></Icon>
