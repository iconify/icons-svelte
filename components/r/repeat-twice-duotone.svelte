<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nds8wgdzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nds8wgdzq primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:repeat-twice-duotone" {...props}></Icon>
