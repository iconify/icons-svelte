<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgg03ub4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vgg03ub4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:list-tree" {...props}></Icon>
