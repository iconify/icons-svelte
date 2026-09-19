<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kg9etqbss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="kg9etqbss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:internet-sharing" {...props}></Icon>
