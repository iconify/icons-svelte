<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m953qcc5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m953qcc5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:columns" {...props}></Icon>
