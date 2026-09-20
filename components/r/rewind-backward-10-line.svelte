<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-4i5sbuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m-4i5sbuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rewind-backward-10-line" {...props}></Icon>
