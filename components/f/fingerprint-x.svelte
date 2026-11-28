<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfbo3h2tc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sfbo3h2tc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:fingerprint-x" {...props}></Icon>
