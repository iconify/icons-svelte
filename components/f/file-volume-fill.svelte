<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v06f5ldfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v06f5ldfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-volume-fill" {...props}></Icon>
