<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jnnj1ubqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jnnj1ubqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bell-ringing-fill" {...props}></Icon>
