<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxtphpb7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gxtphpb7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:dislike-line" {...props}></Icon>
