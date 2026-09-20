<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qm43ot0wh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qm43ot0wh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:building-community-sharp" {...props}></Icon>
