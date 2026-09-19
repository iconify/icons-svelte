<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdpop3bik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rdpop3bik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:arrow-bl-circle" {...props}></Icon>
