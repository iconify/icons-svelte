<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hg7dfsboe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hg7dfsboe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:playlist-minimalistic-2-outline" {...props}></Icon>
