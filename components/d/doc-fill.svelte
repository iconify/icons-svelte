<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ry0j3ldww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ry0j3ldww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:doc-fill" {...props}></Icon>
