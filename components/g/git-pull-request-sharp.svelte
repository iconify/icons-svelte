<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhmtq29kc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mhmtq29kc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:git-pull-request-sharp" {...props}></Icon>
