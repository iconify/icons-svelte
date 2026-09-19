<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mk6pn-bph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mk6pn-bph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:mitarashi-dango" {...props}></Icon>
