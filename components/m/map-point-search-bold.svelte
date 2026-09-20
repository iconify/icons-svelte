<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-1-tpf5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y-1-tpf5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:map-point-search-bold" {...props}></Icon>
