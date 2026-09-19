<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ur3vd-8dh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ur3vd-8dh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:do-redo-thin" {...props}></Icon>
