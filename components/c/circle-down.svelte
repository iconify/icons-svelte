<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kycc8uldy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kycc8uldy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:circle-down" {...props}></Icon>
