<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbfo43z0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gbfo43z0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:menu" {...props}></Icon>
