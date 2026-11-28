<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w38u07vkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w38u07vkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:bear" {...props}></Icon>
