<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjo-1vbvf.css';
import '../../css/l/l-88s82ek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vjo-1vbvf"/><path class="l-88s82ek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ommi" {...props}></Icon>
