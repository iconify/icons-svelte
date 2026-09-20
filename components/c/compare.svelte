<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rduz3kbha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rduz3kbha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:compare" {...props}></Icon>
