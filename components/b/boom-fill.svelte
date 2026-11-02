<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bat2twboi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bat2twboi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:boom-fill" {...props}></Icon>
