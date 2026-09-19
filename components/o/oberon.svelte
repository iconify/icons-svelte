<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y49me6bjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y49me6bjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:oberon" {...props}></Icon>
