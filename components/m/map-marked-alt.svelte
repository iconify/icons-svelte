<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hk06r_61c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hk06r_61c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:map-marked-alt" {...props}></Icon>
