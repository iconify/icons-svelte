<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9-f-xd5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c9-f-xd5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:cloud-upload" {...props}></Icon>
