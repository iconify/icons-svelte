<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/px82gccpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="px82gccpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:flip-horizontal-fill" {...props}></Icon>
