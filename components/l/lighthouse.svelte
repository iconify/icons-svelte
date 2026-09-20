<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yn84y0bsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yn84y0bsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:lighthouse" {...props}></Icon>
