<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjf8htb8n.css';
import '../../css/c/cg7sbj33e.css';
import '../../css/i/ix5ht9bxi.css';
import '../../css/z/zh2h96b0l.css';
import '../../css/i/ilz9b8c5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="fjf8htb8n"/><path class="cg7sbj33e"/><path class="ix5ht9bxi"/><path class="zh2h96b0l"/><path class="ilz9b8c5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:melting-face" {...props}></Icon>
