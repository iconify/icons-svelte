<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n02uupbal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="n02uupbal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:bow-and-arrow" {...props}></Icon>
