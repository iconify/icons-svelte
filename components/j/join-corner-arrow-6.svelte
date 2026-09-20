<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gc_8fq-co.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gc_8fq-co"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:join-corner-arrow-6" {...props}></Icon>
