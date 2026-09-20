<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4_3x3bkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n4_3x3bkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:factory-2-line" {...props}></Icon>
