<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/klv4feksd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="klv4feksd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:grocy-dark" {...props}></Icon>
