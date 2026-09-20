<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bgmx5biec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bgmx5biec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:puzzle-fill" {...props}></Icon>
