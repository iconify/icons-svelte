<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oev3t-jft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="oev3t-jft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:fork-outline" {...props}></Icon>
