<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5-fg7bdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u5-fg7bdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kubuntu-dark" {...props}></Icon>
