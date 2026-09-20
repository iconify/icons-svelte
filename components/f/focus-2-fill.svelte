<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwnoa1buf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fwnoa1buf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:focus-2-fill" {...props}></Icon>
