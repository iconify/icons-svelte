<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1xnr0bmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a1xnr0bmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:clovalink" {...props}></Icon>
