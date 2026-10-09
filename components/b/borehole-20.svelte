<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zkmn36bzs.css';
import '../../css/v/vwsuc6gog.css';
import '../../css/u/u3r8q7x0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zkmn36bzs"/><path class="vwsuc6gog"/><path class="u3r8q7x0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:borehole-20" {...props}></Icon>
