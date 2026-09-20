<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cs8_5cw0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cs8_5cw0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:fatrows-filled" {...props}></Icon>
