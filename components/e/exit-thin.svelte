<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nf44gr3hp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nf44gr3hp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:exit-thin" {...props}></Icon>
