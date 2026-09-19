<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aldytac9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="aldytac9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:credit-card" {...props}></Icon>
