<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/s/s68rhqbhc.css';
import '../../css/j/jt3vpacjn.css';
import '../../css/h/h2u6jfbzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="s68rhqbhc"/><path class="jt3vpacjn"/><path class="h2u6jfbzo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:prescription" {...props}></Icon>
