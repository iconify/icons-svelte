<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5jqqd6xs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w5jqqd6xs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:map-outline" {...props}></Icon>
