<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bsdwrm6cp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bsdwrm6cp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:close-circle-2" {...props}></Icon>
