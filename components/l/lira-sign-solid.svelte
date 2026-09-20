<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crw-psynl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="crw-psynl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:lira-sign-solid" {...props}></Icon>
