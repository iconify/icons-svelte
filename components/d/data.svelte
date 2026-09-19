<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgowae9de.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vgowae9de"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:data" {...props}></Icon>
