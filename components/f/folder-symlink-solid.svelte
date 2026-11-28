<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ym6sqko_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ym6sqko_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:folder-symlink-solid" {...props}></Icon>
