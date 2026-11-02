<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ue5444bbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ue5444bbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:butterfly-2-fill" {...props}></Icon>
