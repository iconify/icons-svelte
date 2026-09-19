<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/leg-t8bwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="leg-t8bwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:mail-outlined" {...props}></Icon>
