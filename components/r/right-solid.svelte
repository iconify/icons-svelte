<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xt3eht83u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xt3eht83u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:right-solid" {...props}></Icon>
