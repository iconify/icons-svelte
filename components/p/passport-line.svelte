<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6uq9acit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g6uq9acit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:passport-line" {...props}></Icon>
