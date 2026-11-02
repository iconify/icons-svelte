<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/july0-b8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="july0-b8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hoe-fill" {...props}></Icon>
