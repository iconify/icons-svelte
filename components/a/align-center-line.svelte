<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cepgkhwtc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cepgkhwtc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:align-center-line" {...props}></Icon>
