<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_gb48rxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c_gb48rxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cursor-outline" {...props}></Icon>
