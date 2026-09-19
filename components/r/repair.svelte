<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/y/yf5xtnrqh.css';
import '../../css/f/f45mp1b7q.css';
import '../../css/j/jfffpyiud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="yf5xtnrqh"/><path class="f45mp1b7q"/><path class="jfffpyiud"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:repair" {...props}></Icon>
