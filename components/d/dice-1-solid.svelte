<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k99vk2bjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k99vk2bjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:dice-1-solid" {...props}></Icon>
