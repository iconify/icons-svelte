<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ra_8wxb8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ra_8wxb8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:mask-light" {...props}></Icon>
