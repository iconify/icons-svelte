<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cd1zhtkzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="cd1zhtkzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:midi-12" {...props}></Icon>
