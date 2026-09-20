<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gb874-b1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gb874-b1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:book-cog-2-bold" {...props}></Icon>
