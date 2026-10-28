<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdecgehse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cdecgehse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:book" {...props}></Icon>
