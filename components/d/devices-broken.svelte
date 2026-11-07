<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/f/fkkg3bbkz.css';
import '../../css/u/ubda_ab4e.css';
import '../../css/p/pbcwo2bql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="fkkg3bbkz"/><path class="ubda_ab4e"/><path class="pbcwo2bql"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:devices-broken" {...props}></Icon>
