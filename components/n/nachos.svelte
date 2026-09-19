<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8e32kbig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l8e32kbig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:nachos" {...props}></Icon>
