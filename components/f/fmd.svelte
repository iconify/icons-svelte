<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jeyfkhb4r.css';
import '../../css/t/t7d2d5bdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jeyfkhb4r"/><path class="t7d2d5bdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fmd" {...props}></Icon>
