<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajb4hcbbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="ajb4hcbbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:credit-card" {...props}></Icon>
