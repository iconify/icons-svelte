<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z79hgub3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z79hgub3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:horizon-sea" {...props}></Icon>
