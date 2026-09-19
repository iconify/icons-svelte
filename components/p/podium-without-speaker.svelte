<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2pno_a1u.css';
import '../../css/m/mp1ra6pzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="u2pno_a1u"/><path class="mp1ra6pzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:podium-without-speaker" {...props}></Icon>
