<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r88ackb7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r88ackb7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:myspace" {...props}></Icon>
