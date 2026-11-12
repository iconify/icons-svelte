<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3k-tlztq.css';
import '../../css/u/u552tcc9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w3k-tlztq"/><path class="u552tcc9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mirotalk-light" {...props}></Icon>
