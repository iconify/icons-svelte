<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/t/trw91eb6p.css';
import '../../css/x/xxb9zre8n.css';
import '../../css/b/b_kj357lv.css';
import '../../css/j/jvh7lq1jm.css';
import '../../css/e/ef89_25rv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="trw91eb6p wm-shadow"/><path class="wm-shadow xxb9zre8n"/><path class="b_kj357lv"/><path class="jvh7lq1jm"/><path class="ef89_25rv wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:camera-off" {...props}></Icon>
