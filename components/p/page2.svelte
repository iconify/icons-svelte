<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6kihwb1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m6kihwb1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:page2" {...props}></Icon>
