<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wom0x6b6m.css';
import '../../css/c/cw-owhbls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wom0x6b6m"/><path clip-rule="evenodd" class="cw-owhbls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:question-24" {...props}></Icon>
