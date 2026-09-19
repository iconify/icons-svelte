<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/r/rxd_zkzui.css';
import '../../css/v/vqbyr6ydp.css';
import '../../css/o/oz_6r38tv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="rxd_zkzui"/><path class="vqbyr6ydp"/><path class="oz_6r38tv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:euro-receive" {...props}></Icon>
