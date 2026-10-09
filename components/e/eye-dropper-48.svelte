<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvu3z166w.css';
import '../../css/a/a1dehnyjo.css';
import '../../css/c/c6f6snb_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fvu3z166w"/><path class="a1dehnyjo"/><path class="c6f6snb_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:eye-dropper-48" {...props}></Icon>
