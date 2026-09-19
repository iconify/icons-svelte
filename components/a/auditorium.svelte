<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxap8d_0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hxap8d_0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:auditorium" {...props}></Icon>
