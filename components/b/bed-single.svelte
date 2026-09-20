<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/voj3xbb6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="voj3xbb6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:bed-single" {...props}></Icon>
