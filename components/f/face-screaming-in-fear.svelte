<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gi8pgxhfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="gi8pgxhfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:face-screaming-in-fear" {...props}></Icon>
