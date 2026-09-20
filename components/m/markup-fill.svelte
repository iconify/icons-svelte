<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g07yztbkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g07yztbkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:markup-fill" {...props}></Icon>
