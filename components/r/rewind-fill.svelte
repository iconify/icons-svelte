<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yo9q5npwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yo9q5npwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:rewind-fill" {...props}></Icon>
