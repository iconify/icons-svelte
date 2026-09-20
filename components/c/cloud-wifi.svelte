<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yr4tk2b9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yr4tk2b9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:cloud-wifi" {...props}></Icon>
