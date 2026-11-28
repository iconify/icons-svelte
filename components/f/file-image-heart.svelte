<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/taychab6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="taychab6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:file-image-heart" {...props}></Icon>
