<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q0o5j0b8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q0o5j0b8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ladder-fill" {...props}></Icon>
