<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1gw67brx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="h1gw67brx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:genetics" {...props}></Icon>
