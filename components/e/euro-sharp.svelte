<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zziz7bc6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zziz7bc6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:euro-sharp" {...props}></Icon>
