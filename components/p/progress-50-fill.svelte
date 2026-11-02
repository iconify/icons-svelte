<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uj13y4bfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uj13y4bfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:progress-50-fill" {...props}></Icon>
