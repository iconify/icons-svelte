<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yi8vsubkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="yi8vsubkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:fullscreen-exit" {...props}></Icon>
