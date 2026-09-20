<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmu0wqbvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dmu0wqbvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:mail-check" {...props}></Icon>
