<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tcl4v3bya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tcl4v3bya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:convos-light" {...props}></Icon>
