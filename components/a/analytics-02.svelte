<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/c/c7_9ow3sz.css';
import '../../css/h/hqyz39bub.css';
import '../../css/j/jg1phg1pi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="c7_9ow3sz"/><path class="hqyz39bub"/><path class="jg1phg1pi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:analytics-02" {...props}></Icon>
