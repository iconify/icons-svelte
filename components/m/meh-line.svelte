<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxeo2gbab.css';
import '../../css/q/q8921-8vp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nxeo2gbab"/><path class="q8921-8vp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:meh-line" {...props}></Icon>
