<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hk60czbbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="hk60czbbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:mask" {...props}></Icon>
