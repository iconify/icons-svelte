<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygmodkbob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="ygmodkbob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:map" {...props}></Icon>
