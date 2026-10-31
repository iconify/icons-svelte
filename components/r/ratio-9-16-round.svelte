<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lv9g8xxos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lv9g8xxos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:ratio-9-16-round" {...props}></Icon>
