<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wn67mnb5e.css';
import '../../css/t/t304wbb4h.css';
import '../../css/u/ubbjctbkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wn67mnb5e"/><path class="t304wbb4h"/><path class="ubbjctbkf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:flashlight" {...props}></Icon>
