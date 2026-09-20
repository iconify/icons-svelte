<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oa1e3obbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oa1e3obbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:camera-slash" {...props}></Icon>
