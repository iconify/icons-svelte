<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rs6jf3bos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="rs6jf3bos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:gyroscope" {...props}></Icon>
