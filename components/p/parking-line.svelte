<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fa-uioj6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fa-uioj6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:parking-line" {...props}></Icon>
