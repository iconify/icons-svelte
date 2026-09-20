<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfif4pbcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pfif4pbcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:git-merge-sharp" {...props}></Icon>
