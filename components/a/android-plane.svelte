<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iklu0itxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iklu0itxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:android-plane" {...props}></Icon>
