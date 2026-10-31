<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgme0g3dg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hgme0g3dg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-left-fill-round" {...props}></Icon>
