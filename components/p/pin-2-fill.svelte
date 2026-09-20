<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uu4r2kb_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uu4r2kb_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pin-2-fill" {...props}></Icon>
