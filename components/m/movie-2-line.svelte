<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajnaei5ta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ajnaei5ta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:movie-2-line" {...props}></Icon>
