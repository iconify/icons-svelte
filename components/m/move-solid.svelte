<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zoa16p8ga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zoa16p8ga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:move-solid" {...props}></Icon>
