<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlfp0n0lt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nlfp0n0lt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:kuma" {...props}></Icon>
