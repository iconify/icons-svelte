<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ppie82bxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ppie82bxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:equals-solid" {...props}></Icon>
