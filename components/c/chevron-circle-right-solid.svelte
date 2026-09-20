<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vc4huuc1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vc4huuc1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:chevron-circle-right-solid" {...props}></Icon>
