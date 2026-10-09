<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kko00cc3q.css';
import '../../css/f/fpxrp7fka.css';
import '../../css/e/e_u3u9v2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kko00cc3q"/><path class="fpxrp7fka"/><path class="e_u3u9v2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:district-heating-20" {...props}></Icon>
