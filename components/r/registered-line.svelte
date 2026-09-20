<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5fdhxbie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i5fdhxbie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:registered-line" {...props}></Icon>
