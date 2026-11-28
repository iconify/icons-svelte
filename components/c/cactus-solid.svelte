<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9blg-1qf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y9blg-1qf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:cactus-solid" {...props}></Icon>
