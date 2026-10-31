<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/s/s8iix90tg.css';
import '../../css/t/twsdh9bcf.css';
import '../../css/f/fn9fj5b4u.css';
import '../../css/y/yryqpsi8c.css';
import '../../css/x/x4niebq2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="s8iix90tg wm-shadow"/><path class="twsdh9bcf wm-shadow"/><path class="fn9fj5b4u"/><path class="yryqpsi8c"/><path class="wm-s x4niebq2n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:filter-x" {...props}></Icon>
