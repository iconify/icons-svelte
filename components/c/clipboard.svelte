<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bf-knybbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bf-knybbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:clipboard" {...props}></Icon>
