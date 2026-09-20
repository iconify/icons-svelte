<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxukx6b-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uxukx6b-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:facial-recognition-filled" {...props}></Icon>
