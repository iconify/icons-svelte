<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jizk64bjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jizk64bjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:briefcase-2-line" {...props}></Icon>
