<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upwnikvyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="upwnikvyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:cursor-arrow-light" {...props}></Icon>
