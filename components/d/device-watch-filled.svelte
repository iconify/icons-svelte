<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/parej1hlz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="parej1hlz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-watch-filled" {...props}></Icon>
