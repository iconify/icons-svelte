<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvvo5_beu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yvvo5_beu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:edit-2-ai-line" {...props}></Icon>
