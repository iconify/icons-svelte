<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddmyanztt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ddmyanztt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:magnet-filled" {...props}></Icon>
