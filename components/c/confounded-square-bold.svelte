<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwz5j43hd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dwz5j43hd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:confounded-square-bold" {...props}></Icon>
