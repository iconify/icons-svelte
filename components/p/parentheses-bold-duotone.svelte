<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0cksp2iz.css';
import '../../css/x/xcjnzfb6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i0cksp2iz"/><path class="xcjnzfb6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:parentheses-bold-duotone" {...props}></Icon>
