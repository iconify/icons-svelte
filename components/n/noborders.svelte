<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ke6ghzira.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":960,"height":960};
const content = `<path class="ke6ghzira"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:noborders" {...props}></Icon>
