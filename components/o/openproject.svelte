<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6i7xsbtb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f6i7xsbtb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:openproject" {...props}></Icon>
