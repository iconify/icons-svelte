<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gef3jd1-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gef3jd1-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:cloud-moon-fill-round" {...props}></Icon>
