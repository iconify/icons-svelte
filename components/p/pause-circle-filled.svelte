<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9e34ux8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w9e34ux8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:pause-circle-filled" {...props}></Icon>
