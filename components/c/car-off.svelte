<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/id681_wzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="id681_wzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:car-off" {...props}></Icon>
