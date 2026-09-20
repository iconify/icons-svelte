<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y38-9crzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y38-9crzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:number-9" {...props}></Icon>
