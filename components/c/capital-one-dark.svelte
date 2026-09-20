<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thiduhgzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="thiduhgzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:capital-one-dark" {...props}></Icon>
