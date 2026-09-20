<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fhv3jp_gm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fhv3jp_gm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:arrow-turn-down-large-solid" {...props}></Icon>
