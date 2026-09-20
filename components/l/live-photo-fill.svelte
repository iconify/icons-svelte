<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmw45m5_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bmw45m5_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:live-photo-fill" {...props}></Icon>
