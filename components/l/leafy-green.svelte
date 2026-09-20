<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2wakxbio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m2wakxbio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:leafy-green" {...props}></Icon>
