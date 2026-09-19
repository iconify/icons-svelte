<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6i7a1tli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="s6i7a1tli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:netflix-filled" {...props}></Icon>
