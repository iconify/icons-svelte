<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6f7ajboz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z6f7ajboz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:folder-zip-fill" {...props}></Icon>
