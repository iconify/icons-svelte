<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmuf8cooy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wmuf8cooy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:prettier" {...props}></Icon>
