<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nd8kbrbyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="nd8kbrbyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:cloud-upload-26" {...props}></Icon>
