<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/w/wgssgdcin.css';
import '../../css/i/i7yqh0b7c.css';
import '../../css/e/e1_julwfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="wgssgdcin"/><path class="i7yqh0b7c"/><path class="e1_julwfp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:message-user-01" {...props}></Icon>
