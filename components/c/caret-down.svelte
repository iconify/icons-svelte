<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xh51pmbib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xh51pmbib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:caret-down" {...props}></Icon>
