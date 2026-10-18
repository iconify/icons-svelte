<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/blvm6x9ra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="blvm6x9ra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:frame" {...props}></Icon>
