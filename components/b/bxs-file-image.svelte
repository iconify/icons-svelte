<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ntx99c38x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ntx99c38x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-file-image" {...props}></Icon>
