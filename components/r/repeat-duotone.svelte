<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pc99f6svk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pc99f6svk primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:repeat-duotone" {...props}></Icon>
