<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zw9ju4b-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="zw9ju4b-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:minus" {...props}></Icon>
