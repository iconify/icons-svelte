<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mii1j5e-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mii1j5e-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:comment-add-light" {...props}></Icon>
