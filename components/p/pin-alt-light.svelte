<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/e/eayipj5ml.css';
import '../../css/s/sgz67zbcf.css';
import '../../css/c/czb17zbdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="eayipj5ml"/><path class="sgz67zbcf"/><circle class="czb17zbdq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:pin-alt-light" {...props}></Icon>
