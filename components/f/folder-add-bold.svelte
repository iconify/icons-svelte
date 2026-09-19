<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/od1wn8bny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="od1wn8bny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:folder-add-bold" {...props}></Icon>
