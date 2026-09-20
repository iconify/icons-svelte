<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1liz-gjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="k1liz-gjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-on-swing" {...props}></Icon>
