<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ds4gxrb-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="ds4gxrb-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-restaurant" {...props}></Icon>
