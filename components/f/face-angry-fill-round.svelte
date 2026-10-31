<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1j18jb1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u1j18jb1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:face-angry-fill-round" {...props}></Icon>
