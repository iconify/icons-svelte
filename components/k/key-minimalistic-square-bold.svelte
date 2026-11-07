<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5zd-yeve.css';
import '../../css/i/i5wpqgyez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x5zd-yeve"/><path clip-rule="evenodd" class="i5wpqgyez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:key-minimalistic-square-bold" {...props}></Icon>
