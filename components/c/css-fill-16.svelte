<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2cni_bxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v2cni_bxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:css-fill-16" {...props}></Icon>
