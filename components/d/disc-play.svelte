<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndq2ubb8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ndq2ubb8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:disc-play" {...props}></Icon>
