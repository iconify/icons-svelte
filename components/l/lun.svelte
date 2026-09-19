<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ig3pv1hce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ig3pv1hce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:lun" {...props}></Icon>
