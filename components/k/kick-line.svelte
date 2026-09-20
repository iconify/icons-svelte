<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0g4gkbld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g0g4gkbld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:kick-line" {...props}></Icon>
