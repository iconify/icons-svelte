<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xti4taclw.css';
import '../../css/p/pr5hkx2sg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xti4taclw"/><path class="pr5hkx2sg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:c-sharp" {...props}></Icon>
