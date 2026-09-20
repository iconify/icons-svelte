<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_khmlbiy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t_khmlbiy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hbo-max-light" {...props}></Icon>
