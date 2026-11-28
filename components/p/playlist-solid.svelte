<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uuwcw0w4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uuwcw0w4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:playlist-solid" {...props}></Icon>
