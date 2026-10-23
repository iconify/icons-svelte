<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7_x84l6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g7_x84l6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:octagon-pause" {...props}></Icon>
