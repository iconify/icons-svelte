<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/acaajybir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="acaajybir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrows-up-from-line-fill" {...props}></Icon>
