<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxf4odbtj.css';
import '../../css/k/k17ecxb8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hxf4odbtj"/><path class="k17ecxb8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:rename-filled" {...props}></Icon>
