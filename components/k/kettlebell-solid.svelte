<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zk-6q41wh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zk-6q41wh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:kettlebell-solid" {...props}></Icon>
