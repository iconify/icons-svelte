<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qivw3q8uz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qivw3q8uz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:power-tower-flag" {...props}></Icon>
