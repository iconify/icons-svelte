<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o52br_tga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o52br_tga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:clipboard-document" {...props}></Icon>
