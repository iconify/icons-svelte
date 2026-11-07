<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5197zbyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t5197zbyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:playlist-2-outline" {...props}></Icon>
