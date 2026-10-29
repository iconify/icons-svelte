<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilowjdbfq.css';
import '../../css/b/bub42fbya.css';
import '../../css/g/gc0jj5bbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ilowjdbfq"/><path class="bub42fbya"/><path class="gc0jj5bbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:ice-cream" {...props}></Icon>
