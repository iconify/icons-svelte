<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hq40a4d6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hq40a4d6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:brain-cog-fill" {...props}></Icon>
