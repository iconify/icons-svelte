<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yx_8t2b9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yx_8t2b9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:contabo" {...props}></Icon>
