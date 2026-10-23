<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6h4l0i8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d6h4l0i8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:navigation-2" {...props}></Icon>
