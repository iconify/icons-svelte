<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/j/j2jph0baw.css';
import '../../css/q/q04vkubxv.css';
import '../../css/p/p_aybwbyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="j2jph0baw"/><path class="q04vkubxv"/><path class="p_aybwbyu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:mic-vocal" {...props}></Icon>
