<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fa2d_wzze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fa2d_wzze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:aew" {...props}></Icon>
