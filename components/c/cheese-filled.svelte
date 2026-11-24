<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exokwfb4m.css';
import '../../css/s/skhazup6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="exokwfb4m"/><path class="skhazup6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:cheese-filled" {...props}></Icon>
