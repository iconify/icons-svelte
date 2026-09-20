<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjbw58qnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qjbw58qnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-watch-code" {...props}></Icon>
