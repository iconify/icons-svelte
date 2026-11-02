<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0zqmdbih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m0zqmdbih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rewind-backward-square-5-line" {...props}></Icon>
