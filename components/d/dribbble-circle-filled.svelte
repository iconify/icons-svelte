<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jy0jeibud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="jy0jeibud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:dribbble-circle-filled" {...props}></Icon>
