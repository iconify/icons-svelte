<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/s/s5vktnbeo.css';
import '../../css/u/unskt_bda.css';
import '../../css/t/tcghh8b0d.css';
import '../../css/m/mon8s9lvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="s5vktnbeo"/><path class="unskt_bda"/><path class="tcghh8b0d"/><path class="mon8s9lvs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:biometric-access" {...props}></Icon>
