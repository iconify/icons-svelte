<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oarmztb3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oarmztb3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:precision" {...props}></Icon>
