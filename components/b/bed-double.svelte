<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/w/w-1c8gqjv.css';
import '../../css/a/a73y9lsqi.css';
import '../../css/a/avujdqbmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="w-1c8gqjv"/><path class="a73y9lsqi"/><path class="avujdqbmn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:bed-double" {...props}></Icon>
