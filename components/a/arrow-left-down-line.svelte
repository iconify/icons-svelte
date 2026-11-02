<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fadjvvb-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fadjvvb-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-left-down-line" {...props}></Icon>
