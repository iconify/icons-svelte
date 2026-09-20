<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlszn25vu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vlszn25vu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:forward-end-mini-line" {...props}></Icon>
