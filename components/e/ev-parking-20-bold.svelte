<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6forwbcg.css';
import '../../css/k/kh20glbaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="h6forwbcg"/><path class="kh20glbaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ev-parking-20-bold" {...props}></Icon>
