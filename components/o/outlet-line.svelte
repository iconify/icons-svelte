<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cyaeiccax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cyaeiccax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:outlet-line" {...props}></Icon>
