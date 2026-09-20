<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohee2bcad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ohee2bcad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:log-in" {...props}></Icon>
