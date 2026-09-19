<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/v/v_wvpib4a.css';
import '../../css/m/mpo63bcwo.css';
import '../../css/n/nhfue6ory.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="v_wvpib4a"/><path class="mpo63bcwo"/><path class="nhfue6ory"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:database-stats" {...props}></Icon>
