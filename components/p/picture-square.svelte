<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bign-sb9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bign-sb9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:picture-square" {...props}></Icon>
