<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ticwrhbbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ticwrhbbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:chevron-right-round" {...props}></Icon>
