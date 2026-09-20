<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lm86fbbey.css';
import '../../css/c/c6ug3vbfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lm86fbbey"/><path class="c6ug3vbfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:notifuse" {...props}></Icon>
