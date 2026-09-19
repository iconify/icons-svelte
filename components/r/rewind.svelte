<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tz6qh7b3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tz6qh7b3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:rewind" {...props}></Icon>
