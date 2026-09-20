<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1_f20b8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g1_f20b8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:jstor-light" {...props}></Icon>
