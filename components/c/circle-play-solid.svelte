<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spmsrqbmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="spmsrqbmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:circle-play-solid" {...props}></Icon>
