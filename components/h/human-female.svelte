<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h50wn0ccf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h50wn0ccf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:human-female" {...props}></Icon>
