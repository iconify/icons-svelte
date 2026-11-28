<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/it8jh6fid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="it8jh6fid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:cloud-search-solid" {...props}></Icon>
