<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nsk9mvbbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="nsk9mvbbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:device-rotate" {...props}></Icon>
