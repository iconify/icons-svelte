<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hq9dtbb4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="hq9dtbb4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:house-damage" {...props}></Icon>
