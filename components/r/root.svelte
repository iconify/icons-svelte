<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/luh11ibda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="luh11ibda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:root" {...props}></Icon>
