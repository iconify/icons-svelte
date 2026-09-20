<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fw26gsbaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fw26gsbaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rewind-backward-30-fill" {...props}></Icon>
