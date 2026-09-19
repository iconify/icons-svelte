<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xb5_0-b-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xb5_0-b-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:ankr" {...props}></Icon>
